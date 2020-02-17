batch-size: 128
task-weight: 0.5
loss-output-bound-coeff: 0.0
imitation-weight: 0.5
record-start-size: 10000.0
rollout-step-num: 1
loss-entropy-coeff: 0.0
critic-l2-reg: 0.0003
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
render-eval: False
max-path-step: 5000
bullet-default-PD: False
expert-index: None
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
critic-activation-fn: ['relu', 'relu', 'None']
actor-lr: 0.0003
joint-interpolation: True
replay-start-size: 10000
HLC-frequency: 25
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
max-episode-num: 5000000
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
train-step-num: 1
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
interpolation: False
categorical-distribution: {'v_min': -10, 'v_max': 250, 'n_atoms': 51}
loss-output-smooth-coeff: 2.0
reward-scale: 0.1
filter-torque: False
epoch-step-num: 5000000
action-dim: 12
Physics-frequency: 1000
env-id: HumanoidBalanceFilter-v0
gamma: 0.955
tau: 0.001
prioritized-exp-replay: True
squash-action: True
LLC-frequency: 500
dsr-gait-freq: 1.667
actor-l2-reg: 0.0003
max-step-num: 2500000000
dsr-gait-period: 0.6
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
actor-layer-size: [256, 256]
loss-output-diff-coeff: 0
gating-index: None
gating-layer-size: [32, 32]
n-step: 1
max-path-num: 20
filter-action: True
actor-activation-fn: ['relu', 'relu', 'None']
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
max-test-time: 10
max-train-time: 10
total-step-num: 2500000000
expert-num: 4
actor-weight-decay: 1e-06
critic-lr: 0.0003
gating-activation-fn: ['relu', 'relu', 'None']
state-dim: 23
replay-buffer-size: 1000000
critic-layer-size: [256, 256]
epoch-num: 500
test-num: 4
critic-weight-decay: 1e-06
replay-ratio: 1
