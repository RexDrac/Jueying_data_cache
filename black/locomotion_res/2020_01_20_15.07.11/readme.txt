n-step: 1
bullet-default-PD: False
LLC-frequency: 500
max-test-time: 10
gamma: 0.955
max-step-num: 2500000000
reward-scale: 0.1
joint-interpolation: True
gating-activation-fn: ['relu', 'relu', 'None']
dsr-gait-period: 0.6
record-start-size: 10000.0
categorical-distribution: {'v_min': -10, 'v_max': 250, 'n_atoms': 51}
loss-entropy-coeff: 0.0
epoch-num: 500
loss-output-smooth-coeff: 2.0
expert-num: 4
train-step-num: 1
actor-lr: 0.0003
env-id: HumanoidBalanceFilter-v0
gating-index: None
gating-layer-size: [32, 32]
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
critic-activation-fn: ['relu', 'relu', 'None']
rollout-step-num: 1
expert-index: None
action-dim: 12
replay-start-size: 10000
Physics-frequency: 1000
loss-output-bound-coeff: 0.0
actor-activation-fn: ['relu', 'relu', 'None']
max-path-num: 20
critic-lr: 0.0003
imitation-weight: 0.5
squash-action: True
replay-buffer-size: 1000000
critic-layer-size: [256, 256]
tau: 0.001
critic-weight-decay: 1e-06
epoch-step-num: 5000000
batch-size: 128
actor-layer-size: [256, 256]
max-train-time: 10
loss-output-diff-coeff: 0
test-num: 4
replay-ratio: 1
total-step-num: 2500000000
render-eval: False
HLC-frequency: 25
critic-l2-reg: 0.0003
state-dim: 23
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
task-weight: 0.5
actor-l2-reg: 0.0003
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
filter-action: True
max-path-step: 5000
actor-weight-decay: 1e-06
max-episode-num: 5000000
dsr-gait-freq: 1.667
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
prioritized-exp-replay: True
interpolation: False
filter-torque: False
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
