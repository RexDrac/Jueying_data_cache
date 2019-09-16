env-id: HumanoidBalanceFilter-v0
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
max-test-time: 10
train-step-num: 1
render-eval: False
record-start-size: 10000.0
Physics-frequency: 1000
gating-activation-fn: ['relu', 'relu', 'None']
filter-action: True
n-step: 1
actor-l2-reg: 0.0003
reward-scale: 0.1
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
loss-output-bound-coeff: 0.0
actor-layer-size: [256, 256]
replay-buffer-size: 1000000
bullet-default-PD: False
dsr-gait-freq: 1.667
gating-index: None
HLC-frequency: 25
max-episode-num: 5000000
task-weight: 0.5
critic-weight-decay: 1e-06
LLC-frequency: 500
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
state-dim: 23
loss-output-diff-coeff: 0
rollout-step-num: 1
critic-lr: 0.0003
filter-torque: False
total-step-num: 2500000000
replay-ratio: 1
actor-lr: 0.0003
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
max-train-time: 10
loss-entropy-coeff: 0.0
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
joint-interpolation: True
prioritized-exp-replay: True
gating-layer-size: [32, 32]
max-step-num: 2500000000
actor-weight-decay: 1e-06
max-path-step: 5000
loss-output-smooth-coeff: 0.5
critic-layer-size: [256, 256]
batch-size: 128
action-dim: 12
squash-action: True
interpolation: False
replay-start-size: 10000
epoch-num: 500
expert-num: 4
critic-l2-reg: 0.0003
actor-activation-fn: ['relu', 'relu', 'None']
gamma: 0.955
critic-activation-fn: ['relu', 'relu', 'None']
categorical-distribution: {'v_max': 250, 'n_atoms': 51, 'v_min': -10}
expert-index: None
epoch-step-num: 5000000
dsr-gait-period: 0.6
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
imitation-weight: 0.5
tau: 0.001
test-num: 4
max-path-num: 20
